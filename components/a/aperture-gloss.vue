<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxz461bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yxz461bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:aperture-gloss" /></template>
