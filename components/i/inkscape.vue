<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3ffykbsf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="g3ffykbsf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:inkscape" /></template>
