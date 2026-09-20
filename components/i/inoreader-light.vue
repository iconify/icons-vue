<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o5db48gif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="o5db48gif"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:inoreader-light" /></template>
