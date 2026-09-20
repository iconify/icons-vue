<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p13hrnsvk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p13hrnsvk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:diamond-16" /></template>
