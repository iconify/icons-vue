<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f2c0v3b3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="f2c0v3b3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:light-bulb-16" /></template>
