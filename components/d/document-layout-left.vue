<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_ieabb_g.css';
import '../../css/r/r2qotkj1w.css';
import '../../css/i/i1958g00u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_ieabb_g"/><rect class="r2qotkj1w"/><path class="i1958g00u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uim:document-layout-left" /></template>
