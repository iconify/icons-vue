<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgjmi9bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xgjmi9bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:circle-chevron-up-solid" /></template>
