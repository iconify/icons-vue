<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/eh06vnbum.css';
import '../../css/h/htce_l0gk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="eh06vnbum"/><path class="htce_l0gk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:catalog" /></template>
