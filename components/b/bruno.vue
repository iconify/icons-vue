<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3gl-5byj.css';
import '../../css/a/aepino0ac.css';
import '../../css/g/go-_ugbik.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="q3gl-5byj"/><path class="aepino0ac"/><path class="go-_ugbik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:bruno" /></template>
