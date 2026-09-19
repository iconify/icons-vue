<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j53pjmbhi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j53pjmbhi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:calculator" /></template>
