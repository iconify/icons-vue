<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/u/ubq5zrksv.css';
import '../../css/a/as6uu1fdt.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG1IxIVcxW"><g class="aql7dnt-u"><path class="ubq5zrksv"/><path class="as6uu1fdt"/></g></mask></defs><path mask="url(#SVG1IxIVcxW)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:exchange-four" /></template>
