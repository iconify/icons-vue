<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up2j63u8p.css';
import '../../css/g/gwo484bfx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="up2j63u8p"/><path class="gwo484bfx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-input-open" /></template>
