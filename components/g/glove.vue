<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fy3qev87z.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGrN7KDbir"><path class="fy3qev87z"/></mask></defs><path mask="url(#SVGrN7KDbir)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:glove" /></template>
