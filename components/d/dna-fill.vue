<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbw2nob3i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbw2nob3i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:dna-fill" /></template>
