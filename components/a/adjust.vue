<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar07nbijb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar07nbijb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:adjust" /></template>
