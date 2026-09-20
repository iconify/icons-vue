<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fiadl4ble.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fiadl4ble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:gold" /></template>
