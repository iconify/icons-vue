<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kix090lwy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kix090lwy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:bank-of-america" /></template>
