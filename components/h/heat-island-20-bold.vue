<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_695na3e.css';
import '../../css/b/b3-608noy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="k_695na3e"/><path class="b3-608noy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-island-20-bold" /></template>
