<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/odpi9ebdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="odpi9ebdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:calculator-16-solid" /></template>
