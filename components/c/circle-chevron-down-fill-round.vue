<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oo8fb39gf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oo8fb39gf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:circle-chevron-down-fill-round" /></template>
