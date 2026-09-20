<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dlxh3ub9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-2,"top":-2};
const content = `<path class="dlxh3ub9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chevrons-circle-right-f" /></template>
