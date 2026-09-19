<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k73w4j2dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="k73w4j2dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:brush" /></template>
