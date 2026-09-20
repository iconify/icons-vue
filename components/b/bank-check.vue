<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aymr-nlwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aymr-nlwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:bank-check" /></template>
