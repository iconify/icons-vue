<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4b25ttjs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g4b25ttjs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:grid-squares-check" /></template>
