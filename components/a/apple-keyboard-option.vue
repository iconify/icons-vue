<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rdo397bby.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rdo397bby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:apple-keyboard-option" /></template>
