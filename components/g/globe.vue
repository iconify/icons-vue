<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/d/dkbc58bxi.css';
import '../../css/o/or039z06o.css';
import '../../css/h/h3zgu7-gy.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpKjpocWi"><g class="aql7dnt-u"><path class="dkbc58bxi"/><path clip-rule="evenodd" class="or039z06o"/><path class="h3zgu7-gy"/></g></mask></defs><path mask="url(#SVGpKjpocWi)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:globe" /></template>
