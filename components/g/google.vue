<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eftaeeh0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eftaeeh0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxl:google" /></template>
