<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uy5o0g0_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uy5o0g0_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codex:link" /></template>
