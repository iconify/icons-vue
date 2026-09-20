<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7e3h4kof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7e3h4kof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:ghost-line" /></template>
