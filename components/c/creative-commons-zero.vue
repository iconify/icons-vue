<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wybm_abdc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wybm_abdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:creative-commons-zero" /></template>
