<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7_udfb7x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="c7_udfb7x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-block:basic-ui-remove" /></template>
