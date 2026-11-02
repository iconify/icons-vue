<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sfsj6eblw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sfsj6eblw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:disc-line" /></template>
