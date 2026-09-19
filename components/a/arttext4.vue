<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_leqbidc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":512};
const content = `<path class="q_leqbidc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:arttext4" /></template>
