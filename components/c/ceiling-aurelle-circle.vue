<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t_ru9otgs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_ru9otgs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ceiling-aurelle-circle" /></template>
