<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/f/fpx-00njb.css';
import '../../css/m/m04ageo3b.css';
import '../../css/h/h80grackm.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQ8VYnwRN"><g class="s9cl3zbei"><circle class="fpx-00njb"/><path class="m04ageo3b"/><path class="h80grackm"/></g></mask></defs><path mask="url(#SVGQ8VYnwRN)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:lock-one" /></template>
