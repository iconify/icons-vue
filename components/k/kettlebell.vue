<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qly5ijb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qly5ijb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:kettlebell" /></template>
