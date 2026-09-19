<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxnw4-snz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mxnw4-snz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:home" /></template>
