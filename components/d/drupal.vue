<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aa4p5bdyh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aa4p5bdyh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:drupal" /></template>
