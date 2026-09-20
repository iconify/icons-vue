<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_b70x2np.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="u_b70x2np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:fork-beside-knife" /></template>
