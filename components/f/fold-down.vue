<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thui0ru5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="thui0ru5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:fold-down" /></template>
