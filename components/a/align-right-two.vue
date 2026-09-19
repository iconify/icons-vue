<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l0e433kwc.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9ccM2cls"><path class="l0e433kwc"/></mask></defs><path mask="url(#SVG9ccM2cls)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:align-right-two" /></template>
