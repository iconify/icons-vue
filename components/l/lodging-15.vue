<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ptp8j_z-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="ptp8j_z-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:lodging-15" /></template>
