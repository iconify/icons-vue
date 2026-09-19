<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gpp7pcb8r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gpp7pcb8r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="codicon:file-submodule" /></template>
