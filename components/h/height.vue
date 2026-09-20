<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aq6c9gc0r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="aq6c9gc0r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:height" /></template>
