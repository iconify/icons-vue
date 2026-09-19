<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/ro9thljwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="ro9thljwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:funnel-fill" /></template>
