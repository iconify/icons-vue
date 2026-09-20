<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uq7ursrio.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uq7ursrio"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:dashboard-3" /></template>
