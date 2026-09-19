<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/drn7cfb8z.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQsUaMe6L"><path class="drn7cfb8z"/></mask></defs><path mask="url(#SVGQsUaMe6L)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:hexagon-one" /></template>
