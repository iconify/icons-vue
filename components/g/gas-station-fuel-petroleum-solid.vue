<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m998mkbkw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="m998mkbkw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:gas-station-fuel-petroleum-solid" /></template>
