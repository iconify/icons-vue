<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vdcn49b2p.css';
import '../../css/z/ze_2m6b8h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="vdcn49b2p"/><path class="ze_2m6b8h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:file-directory-symlink-16" /></template>
