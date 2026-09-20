<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nf17_8bfr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nf17_8bfr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:compact-disk-fill" /></template>
