<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/th3nx3bbc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="th3nx3bbc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:expand-down" /></template>
