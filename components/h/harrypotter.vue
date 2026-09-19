<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxggr_brq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1025,"height":886};
const content = `<path class="mxggr_brq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:harrypotter" /></template>
