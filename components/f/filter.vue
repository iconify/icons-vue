<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xcsnyg2hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xcsnyg2hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gridicons:filter" /></template>
