<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sppmp4bgw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="sppmp4bgw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:issue-type-objective" /></template>
