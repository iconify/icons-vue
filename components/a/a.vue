<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvr3so9tk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvr3so9tk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:a" /></template>
