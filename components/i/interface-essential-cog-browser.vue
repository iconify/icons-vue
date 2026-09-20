<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z84met-5h.css';
import '../../css/n/nr3dqcmlz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="z84met-5h"/><path class="nr3dqcmlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-cog-browser" /></template>
