<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_oajib1w.css';
import '../../css/m/mur108jyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_oajib1w"/><path class="mur108jyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:image-arrow-down" /></template>
