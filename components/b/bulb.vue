<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wjbhn1xhs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wjbhn1xhs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:bulb" /></template>
