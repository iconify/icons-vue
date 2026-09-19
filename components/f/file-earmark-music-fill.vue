<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cxlyxi02t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="cxlyxi02t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-earmark-music-fill" /></template>
