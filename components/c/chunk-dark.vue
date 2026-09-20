<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qkf_nqv3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":65,"height":65,"left":33};
const content = `<path class="qkf_nqv3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:chunk-dark" /></template>
