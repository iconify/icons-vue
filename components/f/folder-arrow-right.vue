<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gejt_2bph.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gejt_2bph"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:folder-arrow-right" /></template>
