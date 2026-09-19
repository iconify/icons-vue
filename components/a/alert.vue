<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5wxdzbeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":42,"height":42};
const content = `<path class="l5wxdzbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="topcoat:alert" /></template>
