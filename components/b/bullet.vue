<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mc5xhwlwg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mc5xhwlwg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:bullet" /></template>
