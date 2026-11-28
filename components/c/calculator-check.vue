<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gvv330bbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gvv330bbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:calculator-check" /></template>
