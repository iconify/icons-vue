<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzp-f_lps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzp-f_lps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="typcn:arrow-repeat-outline" /></template>
