<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k9t1pibft.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k9t1pibft"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:json" /></template>
