<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trnzyybym.css';
import '../../css/s/shqj82b5l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="trnzyybym"/><path class="shqj82b5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="nonicons:keyword-16" /></template>
