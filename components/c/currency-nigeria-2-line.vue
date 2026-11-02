<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p85rznbwz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p85rznbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:currency-nigeria-2-line" /></template>
