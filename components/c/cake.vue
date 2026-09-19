<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmd31ubyp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gmd31ubyp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:cake" /></template>
