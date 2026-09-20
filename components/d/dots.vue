<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc-31ibxl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc-31ibxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dots" /></template>
