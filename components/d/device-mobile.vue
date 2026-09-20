<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftz8nnb_a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":10,"height":16};
const content = `<path class="ftz8nnb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:device-mobile" /></template>
