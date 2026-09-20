<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9p_rvbsx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9p_rvbsx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:bowling-ball" /></template>
