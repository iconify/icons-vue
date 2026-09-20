<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bvd2-0vsm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bvd2-0vsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:disc-fill" /></template>
