<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z_h52ebxj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z_h52ebxj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-teen-gloss" /></template>
