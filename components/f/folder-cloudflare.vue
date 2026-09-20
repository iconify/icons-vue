<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ceuecc10c.css';
import '../../css/d/dpy7q7boi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ceuecc10c"/><path class="dpy7q7boi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-cloudflare" /></template>
