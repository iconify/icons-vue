<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/equdfwqlp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="equdfwqlp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="rivet-icons:data-solid" /></template>
