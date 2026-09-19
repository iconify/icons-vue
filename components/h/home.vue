<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tcn075b6r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tcn075b6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:home" /></template>
