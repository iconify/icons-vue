<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bngvwn_2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bngvwn_2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:alphabetical-sorting-2" /></template>
