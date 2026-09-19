<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/z/zdy6akj0d.css';
import '../../css/s/s3hkxbb6p.css';
import '../../css/s/s19sxdqbo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlEjTBP1C"><g class="s9cl3zbei"><path clip-rule="evenodd" class="zdy6akj0d"/><path class="s3hkxbb6p"/><path class="s19sxdqbo"/></g></mask></defs><path mask="url(#SVGlEjTBP1C)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:delete-themes" /></template>
