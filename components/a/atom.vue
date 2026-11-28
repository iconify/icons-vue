<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppnlvjbza.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ppnlvjbza"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:atom" /></template>
