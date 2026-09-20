<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khz2yzbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-4.5};
const content = `<path class="khz2yzbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:arrow-down" /></template>
