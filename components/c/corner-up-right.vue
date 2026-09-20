<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1cnn4fhv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d1cnn4fhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uis:corner-up-right" /></template>
