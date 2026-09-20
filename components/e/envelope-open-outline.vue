<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1e8wfblg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="i1e8wfblg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="teenyicons:envelope-open-outline" /></template>
