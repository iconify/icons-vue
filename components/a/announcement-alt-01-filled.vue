<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzf6qpbek.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzf6qpbek"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:announcement-alt-01-filled" /></template>
