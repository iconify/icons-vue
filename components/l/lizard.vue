<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv01ucbgq.css';
import '../../css/b/bp49p9l1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="bv01ucbgq"/><path class="bp49p9l1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:lizard" /></template>
