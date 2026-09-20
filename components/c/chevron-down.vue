<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eo58ugbcz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eo58ugbcz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nrk:chevron-down" /></template>
