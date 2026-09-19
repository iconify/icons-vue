<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_p2r6ryq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s_p2r6ryq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:creole" /></template>
