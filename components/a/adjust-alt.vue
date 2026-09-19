<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oqsh6n6fl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="oqsh6n6fl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:adjust-alt" /></template>
