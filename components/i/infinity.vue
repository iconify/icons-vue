<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b-249hgfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="b-249hgfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:infinity" /></template>
