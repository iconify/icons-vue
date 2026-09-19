<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/t/tk146ob_t.css';
import '../../css/s/sluqj5bks.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG3OxGFd7z"><g class="v3_i3wktz"><path class="tk146ob_t"/><path class="sluqj5bks"/></g></mask></defs><path mask="url(#SVG3OxGFd7z)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:cross-ring" /></template>
