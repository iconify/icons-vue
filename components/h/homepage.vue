<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dwkt19xnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dwkt19xnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:homepage" /></template>
