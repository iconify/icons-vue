<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jknxtgxtf.css';
import '../../css/x/xf60uybiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="jknxtgxtf"/><path class="xf60uybiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:folder-cargo-open" /></template>
