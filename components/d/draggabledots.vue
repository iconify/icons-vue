<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/stguk9bgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stguk9bgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:draggabledots" /></template>
