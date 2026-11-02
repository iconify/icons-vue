<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt6z-vbxw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vt6z-vbxw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:battery-automotive-fill" /></template>
