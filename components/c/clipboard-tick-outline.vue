<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uax_rrxbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="uax_rrxbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:clipboard-tick-outline" /></template>
