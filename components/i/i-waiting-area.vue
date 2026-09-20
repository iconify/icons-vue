<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mas2u-b0z.css';
import '../../css/u/u2y7rxb9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="mas2u-b0z"/><path class="u2y7rxb9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="medical-icon:i-waiting-area" /></template>
