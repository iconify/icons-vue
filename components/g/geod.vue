<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yl4svbcyn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yl4svbcyn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:geod" /></template>
