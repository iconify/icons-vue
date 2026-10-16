<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y2v02vmol.css';
import '../../css/m/m4hmbobqb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y2v02vmol"/><path class="m4hmbobqb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:letter-case-20" /></template>
