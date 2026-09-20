<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ob886xb6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="ob886xb6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:heartbroken" /></template>
