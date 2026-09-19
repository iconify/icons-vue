<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y8qun1bmd.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPM99xcmU"><path class="y8qun1bmd"/></mask></defs><path mask="url(#SVGPM99xcmU)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:cross-society" /></template>
