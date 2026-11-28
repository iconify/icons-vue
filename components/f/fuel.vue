<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfht2wbva.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mfht2wbva"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:fuel" /></template>
