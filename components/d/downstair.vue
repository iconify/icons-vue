<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bff9_4afs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":17,"height":16};
const content = `<path class="bff9_4afs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si-glyph:downstair" /></template>
