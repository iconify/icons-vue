<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rqyl0nvla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rqyl0nvla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconamoon:cheque" /></template>
