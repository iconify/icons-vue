<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/baacqjbhs.css';
import '../../css/j/j90iobcke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="baacqjbhs"/><path class="j90iobcke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filebrowser-quantum-dark" /></template>
