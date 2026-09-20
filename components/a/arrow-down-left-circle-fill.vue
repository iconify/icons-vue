<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fxx6fwb7n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxx6fwb7n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:arrow-down-left-circle-fill" /></template>
