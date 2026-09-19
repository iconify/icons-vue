<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9-r-6e9w.css';
import '../../css/s/s2k9j_-go.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s9-r-6e9w"/><path class="s2k9j_-go"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cil:featured-playlist" /></template>
