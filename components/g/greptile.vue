<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfkt53w_x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wfkt53w_x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:greptile" /></template>
