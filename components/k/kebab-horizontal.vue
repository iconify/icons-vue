<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oukk7ab7a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":13,"height":16};
const content = `<path class="oukk7ab7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:kebab-horizontal" /></template>
