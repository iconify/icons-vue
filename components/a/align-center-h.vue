<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cg6_u8xll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg6_u8xll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:align-center-h" /></template>
