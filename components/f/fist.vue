<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hmaojwd9t.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG0F4f16iy"><path class="hmaojwd9t"/></mask></defs><path mask="url(#SVG0F4f16iy)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:fist" /></template>
