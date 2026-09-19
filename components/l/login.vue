<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubvq29b5w.css';
import '../../css/u/uoci6xb9o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ubvq29b5w"/><path class="uoci6xb9o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:login" /></template>
