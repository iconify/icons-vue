<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/plnner7oi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="plnner7oi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:link-slash" /></template>
