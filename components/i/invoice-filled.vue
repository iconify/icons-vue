<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3p_plb9q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="e3p_plb9q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:invoice-filled" /></template>
