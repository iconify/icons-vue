<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q4f9te_7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="q4f9te_7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:link-remove-fill-12" /></template>
