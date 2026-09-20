<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dpmyxrb0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dpmyxrb0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:folder-3-line" /></template>
