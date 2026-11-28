<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar7a0pkpj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ar7a0pkpj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:globe-x" /></template>
