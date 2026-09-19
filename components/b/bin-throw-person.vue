<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t3l9shbff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t3l9shbff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:bin-throw-person" /></template>
