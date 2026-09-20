<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lz5tfxbtx.css';
import '../../css/l/l0ryvi2pe.css';
import '../../css/u/ug6nvcb0n.css';
import '../../css/e/exbu-tbth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="lz5tfxbtx"/><path class="l0ryvi2pe"/><path class="ug6nvcb0n"/><path class="exbu-tbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:content-files-notepad" /></template>
