<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j65qxbk-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="j65qxbk-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:hashnode" /></template>
