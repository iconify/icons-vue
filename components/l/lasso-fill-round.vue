<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rjm-jcbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rjm-jcbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lasso-fill-round" /></template>
