<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xv13ywbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xv13ywbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:keep" /></template>
