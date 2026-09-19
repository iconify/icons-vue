<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_uny6b8v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_uny6b8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:horizontal-align-center-filled" /></template>
