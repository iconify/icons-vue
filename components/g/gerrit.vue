<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qleiye-zv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qleiye-zv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:gerrit" /></template>
