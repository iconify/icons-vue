<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drgbd2w6h.css';
import '../../css/c/c3_ibvh4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drgbd2w6h"/><path class="c3_ibvh4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:chevrons-down" /></template>
