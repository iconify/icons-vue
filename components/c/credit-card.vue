<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gikm-gb_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gikm-gb_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:credit-card" /></template>
