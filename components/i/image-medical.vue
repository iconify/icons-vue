<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jj_f8me5y.css';
import '../../css/l/ljxqdzyof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="jj_f8me5y"/><path class="ljxqdzyof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:image-medical" /></template>
