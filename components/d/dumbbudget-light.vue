<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/anwk4fogy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="anwk4fogy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:dumbbudget-light" /></template>
