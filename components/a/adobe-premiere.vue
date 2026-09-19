<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hsum-u5pz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hsum-u5pz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:adobe-premiere" /></template>
