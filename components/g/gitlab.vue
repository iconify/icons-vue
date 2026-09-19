<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j745orp_y.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtKIw9llJ"><path class="j745orp_y"/></mask></defs><path mask="url(#SVGtKIw9llJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:gitlab" /></template>
