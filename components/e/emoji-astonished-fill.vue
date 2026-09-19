<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1yz3bbjc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r1yz3bbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:emoji-astonished-fill" /></template>
