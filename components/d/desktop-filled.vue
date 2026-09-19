<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql6c7ubyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ql6c7ubyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:desktop-filled" /></template>
