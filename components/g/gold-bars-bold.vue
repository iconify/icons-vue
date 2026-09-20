<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l_yapab2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_yapab2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:gold-bars-bold" /></template>
