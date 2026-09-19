<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bx7st-bid.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGDulKzedE"><path class="bx7st-bid"/></mask></defs><path mask="url(#SVGDulKzedE)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:left-one" /></template>
