<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8x7susgg.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHtA3wd4c"><path class="d8x7susgg"/></mask></defs><path mask="url(#SVGHtA3wd4c)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bad-one" /></template>
