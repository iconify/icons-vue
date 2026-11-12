<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v9t-uvgki.css';
import '../../css/j/j90iobcke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="v9t-uvgki"/><path class="j90iobcke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filebrowser-quantum-dark" /></template>
