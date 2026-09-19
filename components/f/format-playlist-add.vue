<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3p5n_b4n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":432,"height":384};
const content = `<path class="f3p5n_b4n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="zmdi:format-playlist-add" /></template>
