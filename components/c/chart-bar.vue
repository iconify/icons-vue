<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9ofttbku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s9ofttbku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="charm:chart-bar" /></template>
