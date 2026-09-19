<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ohxk8dnoz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ohxk8dnoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:drupal" /></template>
