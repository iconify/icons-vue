<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/srt553b7w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="srt553b7w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:italic" /></template>
