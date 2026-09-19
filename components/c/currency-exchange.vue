<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gv8qhim-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gv8qhim-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:currency-exchange" /></template>
