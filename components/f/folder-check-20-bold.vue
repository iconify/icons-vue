<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdl9mfbpe.css';
import '../../css/a/aqsnv9bnd.css';
import '../../css/s/sh06c0bcw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vdl9mfbpe"/><path class="aqsnv9bnd"/><path class="sh06c0bcw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:folder-check-20-bold" /></template>
