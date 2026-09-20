<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c3yr46bdt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="c3yr46bdt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:help-16" /></template>
