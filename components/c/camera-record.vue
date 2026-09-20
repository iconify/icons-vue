<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/grdj55bza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="grdj55bza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:camera-record" /></template>
