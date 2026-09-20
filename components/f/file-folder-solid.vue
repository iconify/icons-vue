<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmn7a4bpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="rmn7a4bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:file-folder-solid" /></template>
