<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbzfsczgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="lbzfsczgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:diff" /></template>
