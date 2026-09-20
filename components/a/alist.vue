<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rykkm0uiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rykkm0uiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:alist" /></template>
