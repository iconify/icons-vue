<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg1hkqrlf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg1hkqrlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:braces-solid" /></template>
