<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lho_ys8eu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lho_ys8eu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:box" /></template>
