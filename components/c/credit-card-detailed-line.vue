<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vvfunrbcp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vvfunrbcp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:credit-card-detailed-line" /></template>
