<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxhe1qt7r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="mxhe1qt7r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:github-fill-16" /></template>
