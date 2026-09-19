<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pdb6pe1ke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":448};
const content = `<path class="pdb6pe1ke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:library" /></template>
