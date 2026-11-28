<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exk7c48uf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exk7c48uf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:clipboard-medical-x" /></template>
