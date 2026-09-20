<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s_mpl-t0u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s_mpl-t0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:gable-roofed-shelter-with-spoon-and-knife" /></template>
