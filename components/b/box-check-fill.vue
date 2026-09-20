<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uzjy1cc-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uzjy1cc-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:box-check-fill" /></template>
