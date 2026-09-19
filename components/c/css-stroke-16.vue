<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gomz2yium.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gomz2yium"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:css-stroke-16" /></template>
