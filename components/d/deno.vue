<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hdp1j7-gv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="hdp1j7-gv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:deno" /></template>
