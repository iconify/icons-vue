<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0sruib_n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l0sruib_n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:cross-filled-16" /></template>
