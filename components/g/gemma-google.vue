<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xkvs36v4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xkvs36v4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gemma-google" /></template>
