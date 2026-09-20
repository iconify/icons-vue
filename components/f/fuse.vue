<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmafcacme.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmafcacme"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:fuse" /></template>
