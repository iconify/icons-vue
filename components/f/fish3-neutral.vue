<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xl0k0gb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xl0k0gb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:fish3-neutral" /></template>
