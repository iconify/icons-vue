<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-n6fq1ay.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u-n6fq1ay"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-arrow-right-sharp" /></template>
