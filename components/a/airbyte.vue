<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qxfp7ac1x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qxfp7ac1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:airbyte" /></template>
