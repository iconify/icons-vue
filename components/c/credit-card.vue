<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lerk_xbbj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lerk_xbbj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:credit-card" /></template>
