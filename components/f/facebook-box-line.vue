<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjapdh0be.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qjapdh0be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:facebook-box-line" /></template>
