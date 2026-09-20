<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vwfragbkr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="vwfragbkr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:ferry-jp" /></template>
