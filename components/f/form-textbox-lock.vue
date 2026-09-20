<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nrsp6jjiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nrsp6jjiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:form-textbox-lock" /></template>
