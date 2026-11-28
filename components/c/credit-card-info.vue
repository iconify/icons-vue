<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efr_xsynl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="efr_xsynl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:credit-card-info" /></template>
