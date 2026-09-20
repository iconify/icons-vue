<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gmw_3pbmo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="gmw_3pbmo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:chip-bag-with-chip" /></template>
