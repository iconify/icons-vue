<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqzeqtbqr.css';
import '../../css/f/fa6qugbtz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="pqzeqtbqr"/><path class="fa6qugbtz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ironcalc-dark" /></template>
