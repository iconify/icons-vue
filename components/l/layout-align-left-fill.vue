<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iuz27zgrx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iuz27zgrx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layout-align-left-fill" /></template>
