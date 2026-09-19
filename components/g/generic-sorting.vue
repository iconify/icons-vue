<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pf2wg-b4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="pf2wg-b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:generic-sorting" /></template>
