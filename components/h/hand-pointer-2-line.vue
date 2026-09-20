<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/resxiwg2e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="resxiwg2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:hand-pointer-2-line" /></template>
