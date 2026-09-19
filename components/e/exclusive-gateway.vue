<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/e/ez330t4ze.css';
import '../../css/h/h5g3_-b7x.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG11V2DcGG"><g class="s9cl3zbei"><path class="ez330t4ze"/><path class="h5g3_-b7x"/></g></mask></defs><path mask="url(#SVG11V2DcGG)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:exclusive-gateway" /></template>
