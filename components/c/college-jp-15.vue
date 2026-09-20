<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lsg8cfboz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lsg8cfboz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:college-jp-15" /></template>
