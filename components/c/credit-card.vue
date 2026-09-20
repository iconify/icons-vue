<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sikot-83c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sikot-83c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:credit-card" /></template>
