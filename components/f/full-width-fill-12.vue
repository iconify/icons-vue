<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mjm5n7boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mjm5n7boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:full-width-fill-12" /></template>
