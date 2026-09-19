<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sas-o7bjt.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5YrIXcfC"><path class="sas-o7bjt"/></mask></defs><path mask="url(#SVG5YrIXcfC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bydesign" /></template>
