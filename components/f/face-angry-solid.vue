<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yth3gxboe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yth3gxboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:face-angry-solid" /></template>
