<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m-2gchbtb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m-2gchbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:car-fill-16" /></template>
