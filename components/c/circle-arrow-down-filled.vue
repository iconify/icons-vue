<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ervr_zbjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ervr_zbjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:circle-arrow-down-filled" /></template>
