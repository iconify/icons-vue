<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cbdtere1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cbdtere1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="roentgen:i" /></template>
