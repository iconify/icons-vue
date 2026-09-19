<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q19mp7b0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="q19mp7b0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:bars-descending-align-left" /></template>
