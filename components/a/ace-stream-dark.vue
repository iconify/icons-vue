<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bbmlrht5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bbmlrht5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ace-stream-dark" /></template>
