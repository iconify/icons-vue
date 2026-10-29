<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r-mvzwbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-mvzwbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:book-open-text-solid" /></template>
