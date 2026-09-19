<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/j/j-v2u4nhg.css';
import '../../css/y/y3t5dyb3v.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHJngxcdO"><g class="v3_i3wktz"><path class="j-v2u4nhg"/><path class="y3t5dyb3v"/></g></mask></defs><path mask="url(#SVGHJngxcdO)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:arrow-circle-down" /></template>
