<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w79h7j-7v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":180,"height":180};
const content = `<path class="w79h7j-7v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:earmark-light" /></template>
