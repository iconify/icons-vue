<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/caintxonb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="caintxonb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:bucket" /></template>
