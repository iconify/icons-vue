<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e2xd09b8a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="e2xd09b8a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oi:arrow-thick-left" /></template>
