<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzmi_jb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gzmi_jb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:deepcool" /></template>
