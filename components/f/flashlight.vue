<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/f/fjagq7bdj.css';
import '../../css/y/ydqauvg5t.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgfK5ncmj"><g class="v3_i3wktz"><path class="fjagq7bdj"/><path class="ydqauvg5t"/></g></mask></defs><path mask="url(#SVGgfK5ncmj)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:flashlight" /></template>
