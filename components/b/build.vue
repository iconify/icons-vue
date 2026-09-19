<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-7fv8ivv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="l-7fv8ivv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:build" /></template>
