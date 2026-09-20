<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jad-edzcj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jad-edzcj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:antennapod" /></template>
