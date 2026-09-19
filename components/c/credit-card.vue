<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxz7a4jmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxz7a4jmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mono-icons:credit-card" /></template>
