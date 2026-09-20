<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ek3w6tbum.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ek3w6tbum"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:face-unhappy" /></template>
