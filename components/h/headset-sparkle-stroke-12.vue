<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v--xoo9qn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="v--xoo9qn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:headset-sparkle-stroke-12" /></template>
