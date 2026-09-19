<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/i/i89f99xzv.css';
import '../../css/k/krgim9y4j.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGqnHOcdqL"><g class="v3_i3wktz"><rect class="i89f99xzv"/><path class="krgim9y4j"/></g></mask></defs><path mask="url(#SVGqnHOcdqL)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:display" /></template>
