<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vz11d19xp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vz11d19xp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:jump-16" /></template>
