<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/arj7difgh.css';
import '../../css/r/rov9kshcy.css';
import '../../css/g/gnoakjtgj.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG0R5Pr0xD"><g class="ft5dv1b6b"><path class="arj7difgh"/><path class="rov9kshcy"/><path clip-rule="evenodd" class="gnoakjtgj"/></g></mask></defs><path mask="url(#SVG0R5Pr0xD)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:browser-safari" /></template>
