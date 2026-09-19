<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf-c3ibdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gf-c3ibdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bi:file-music-fill" /></template>
