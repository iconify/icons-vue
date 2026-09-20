<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt2cw3b-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt2cw3b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:delete-line" /></template>
