<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hg31zhsfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":506,"height":512};
const content = `<path class="hg31zhsfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:dna" /></template>
