<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gzesfbb8z.css';
import '../../css/q/qccj0vbum.css';
import '../../css/d/dlp7nstpk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gzesfbb8z"/><path class="qccj0vbum"/><circle class="dlp7nstpk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:container-registry" /></template>
