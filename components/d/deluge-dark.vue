<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jo8dgxbkt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jo8dgxbkt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:deluge-dark" /></template>
