<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uf5_0tv0y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":448,"height":512};
const content = `<path class="uf5_0tv0y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-brands:drupal" /></template>
