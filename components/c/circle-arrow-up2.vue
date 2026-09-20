<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ff61ui5pt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ff61ui5pt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrow-up2" /></template>
