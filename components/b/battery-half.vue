<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e-0pk97dv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e-0pk97dv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:battery-half" /></template>
