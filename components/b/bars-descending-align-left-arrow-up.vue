<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s65hwzmez.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="s65hwzmez"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:bars-descending-align-left-arrow-up" /></template>
