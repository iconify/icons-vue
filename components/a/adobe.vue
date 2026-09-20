<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cmgxcm54w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cmgxcm54w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:adobe" /></template>
