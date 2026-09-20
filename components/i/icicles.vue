<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qpz9ytm9t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="qpz9ytm9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:icicles" /></template>
