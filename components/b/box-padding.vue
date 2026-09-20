<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv6l8fblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yv6l8fblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:box-padding" /></template>
