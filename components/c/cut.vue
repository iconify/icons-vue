<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/trc-w2bhn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="trc-w2bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:cut" /></template>
