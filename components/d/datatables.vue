<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pfg5l5b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="pfg5l5b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:datatables" /></template>
