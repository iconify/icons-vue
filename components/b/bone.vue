<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a4o6m2bxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="a4o6m2bxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:bone" /></template>
