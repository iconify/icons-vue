<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/e/e_bqi703z.css';
import '../../css/r/r8r179s3m.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPja92c8y"><g class="aql7dnt-u"><path clip-rule="evenodd" class="e_bqi703z"/><path class="r8r179s3m"/></g></mask></defs><path mask="url(#SVGPja92c8y)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:cuvette" /></template>
