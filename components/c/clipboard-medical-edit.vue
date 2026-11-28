<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sgnvt6b9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sgnvt6b9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clipboard-medical-edit" /></template>
