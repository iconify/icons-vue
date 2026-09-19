<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3n_jhubk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="f3n_jhubk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:google-chrome" /></template>
