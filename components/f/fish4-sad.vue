<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y9e3p7bjr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="y9e3p7bjr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:fish4-sad" /></template>
