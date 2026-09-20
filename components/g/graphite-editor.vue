<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7542ra8w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7542ra8w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:graphite-editor" /></template>
