<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hnd_t9byb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="hnd_t9byb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:idea" /></template>
