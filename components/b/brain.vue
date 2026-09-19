<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1ynlvb2t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q1ynlvb2t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:brain" /></template>
