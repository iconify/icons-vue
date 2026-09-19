<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tajr-w3dr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tajr-w3dr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:crunchbase" /></template>
