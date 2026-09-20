<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s90jwlbfi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="s90jwlbfi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pinhead:book-with-music-notes-eighth" /></template>
