<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a02s0cczt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a02s0cczt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:book-with-arrows-recirculating" /></template>
