<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s77lopbsd.css';
import '../../css/a/ajx-gfbps.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="s77lopbsd"/><path class="ajx-gfbps"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:filebrowser-quantum" /></template>
