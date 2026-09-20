<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sng5_6bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sng5_6bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:arrow-left-square-fill" /></template>
