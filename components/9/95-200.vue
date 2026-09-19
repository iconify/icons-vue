<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxa1debtt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":528,"height":448};
const content = `<path class="hxa1debtt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:95-200" /></template>
