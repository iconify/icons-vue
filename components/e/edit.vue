<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/klzv45b1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":384};
const content = `<path class="klzv45b1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:edit" /></template>
