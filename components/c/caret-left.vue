<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/doch_vycb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="doch_vycb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:caret-left" /></template>
