<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-heh5bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="z-heh5bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:caravan" /></template>
