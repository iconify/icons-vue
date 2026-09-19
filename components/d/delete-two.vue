<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/b/b55bfubsx.css';
import '../../css/i/itkqv0bnq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGDJbpMdSq"><g class="aql7dnt-u"><path class="b55bfubsx"/><path class="itkqv0bnq"/></g></mask></defs><path mask="url(#SVGDJbpMdSq)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:delete-two" /></template>
