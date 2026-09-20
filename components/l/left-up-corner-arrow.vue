<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x38bmab_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x38bmab_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="subway:left-up-corner-arrow" /></template>
