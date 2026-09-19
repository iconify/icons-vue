<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tc3urnw9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tc3urnw9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:mail-read" /></template>
