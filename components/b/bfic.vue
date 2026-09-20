<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v1gqmmbxi.css';
import '../../css/n/nzl6tpgjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1gqmmbxi"/><path class="nzl6tpgjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:bfic" /></template>
