<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/b/baen2yhxr.css';
import '../../css/g/g54p95bma.css';
import '../../css/n/neptv8bgx.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGtEp7Ce7g"><g class="aql7dnt-u"><path class="baen2yhxr"/><circle class="g54p95bma"/><path class="neptv8bgx"/></g></mask></defs><path mask="url(#SVGtEp7Ce7g)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:compass" /></template>
