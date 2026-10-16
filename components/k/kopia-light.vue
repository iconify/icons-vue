<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9daaw4ne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":100,"height":64};
const content = `<path class="w9daaw4ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:kopia-light" /></template>
