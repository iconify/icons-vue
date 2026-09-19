<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bsdwrm6cp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsdwrm6cp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:close-circle-2-duotone" /></template>
