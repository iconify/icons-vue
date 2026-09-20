<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ux2ta2kwe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ux2ta2kwe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:battery-full-fill" /></template>
