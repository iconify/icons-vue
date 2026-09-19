<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lln4j2bfx.css';
import '../../css/m/m7erot3eb.css';
import '../../css/h/humhrf4wy.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGu0sYleFi"><g class="ft5dv1b6b"><path class="lln4j2bfx"/><path class="m7erot3eb"/><path class="humhrf4wy"/></g></mask></defs><path mask="url(#SVGu0sYleFi)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:birthday-cake" /></template>
