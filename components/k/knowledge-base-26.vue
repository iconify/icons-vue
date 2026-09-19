<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yvyfft4ni.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<path class="yvyfft4ni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:knowledge-base-26" /></template>
