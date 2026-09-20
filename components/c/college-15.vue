<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8orsp8wy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="t8orsp8wy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:college-15" /></template>
