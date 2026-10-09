<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g3miqgbxj.css';
import '../../css/b/blbmivddt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g3miqgbxj"/><path class="blbmivddt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:golf-48" /></template>
