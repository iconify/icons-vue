<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shdzjkdzk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="shdzjkdzk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:fish2-neutral" /></template>
