<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mfp6r-iru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="mfp6r-iru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:comment" /></template>
