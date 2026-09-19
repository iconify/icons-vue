<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rt6thsbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1536,"height":1792};
const content = `<path class="rt6thsbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:file-sound-o" /></template>
