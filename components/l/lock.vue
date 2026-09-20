<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo709nj-l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":16};
const content = `<path class="mo709nj-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:lock" /></template>
