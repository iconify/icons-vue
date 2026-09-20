<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g4y_wl45o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":16};
const content = `<path class="g4y_wl45o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:fold-up" /></template>
