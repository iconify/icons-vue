<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv4_7tbkd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sv4_7tbkd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:form-textbox" /></template>
