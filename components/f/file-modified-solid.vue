<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fro4r_rjb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fro4r_rjb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:file-modified-solid" /></template>
