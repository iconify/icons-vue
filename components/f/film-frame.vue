<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iv7f0q5lo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="iv7f0q5lo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons:film-frame" /></template>
