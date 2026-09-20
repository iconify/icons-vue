<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx0bnjbnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="rx0bnjbnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:campsite-with-ruble" /></template>
