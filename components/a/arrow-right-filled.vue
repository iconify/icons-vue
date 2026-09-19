<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xdoc90x5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xdoc90x5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-right-filled" /></template>
