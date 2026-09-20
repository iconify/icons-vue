<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekggfg2gw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ekggfg2gw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:audio-technica" /></template>
