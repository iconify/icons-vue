<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khs-oebse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="khs-oebse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:arrow-down" /></template>
