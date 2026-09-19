<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ucl5_zvmt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ucl5_zvmt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:lightbulb-slash" /></template>
