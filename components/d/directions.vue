<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk858wbhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zk858wbhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:directions" /></template>
