<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a13q3r_5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="a13q3r_5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:ear-atop-slash-with-t" /></template>
