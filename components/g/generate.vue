<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uuywphb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uuywphb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:generate" /></template>
