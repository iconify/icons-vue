<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mu9qfpjil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mu9qfpjil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:horizontal-align-left" /></template>
