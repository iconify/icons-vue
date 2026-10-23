<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-f5gkbaz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-f5gkbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:list-start" /></template>
