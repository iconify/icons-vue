<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aetuanbcc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="aetuanbcc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:clipboard-check-fill-16" /></template>
