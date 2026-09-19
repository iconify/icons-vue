<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v6p0_bl_n.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGWJIstexD"><path class="v6p0_bl_n"/></mask></defs><path mask="url(#SVGWJIstexD)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:lightning" /></template>
