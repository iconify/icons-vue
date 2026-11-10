<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tne-w562i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="tne-w562i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:boolean-subtract" /></template>
