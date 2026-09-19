<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xi57_fbmb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="xi57_fbmb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:diamonds-card" /></template>
