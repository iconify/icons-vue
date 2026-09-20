<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uei7otwae.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uei7otwae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dashboard-3-fill" /></template>
