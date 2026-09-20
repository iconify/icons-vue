<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxn0p0b7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cxn0p0b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:chart-down-b-fill" /></template>
