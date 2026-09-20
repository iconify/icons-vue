<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kffec9iaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="kffec9iaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:circle-outline" /></template>
