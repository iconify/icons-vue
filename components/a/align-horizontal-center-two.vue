<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/khyr1cc7b.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZ1FsecDt"><path class="khyr1cc7b"/></mask></defs><path mask="url(#SVGZ1FsecDt)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:align-horizontal-center-two" /></template>
