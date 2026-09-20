<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxuajgb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxuajgb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:arrow-up-box" /></template>
