<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gq7pqabwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="gq7pqabwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:download" /></template>
