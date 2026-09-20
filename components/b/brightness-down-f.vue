<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u8xe44b8o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-4,"top":-3.5};
const content = `<path class="u8xe44b8o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:brightness-down-f" /></template>
