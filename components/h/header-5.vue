<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llnvy_sqt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-6.5};
const content = `<path class="llnvy_sqt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:header-5" /></template>
