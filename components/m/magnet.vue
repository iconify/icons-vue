<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/e/e6x_babbs.css';
import '../../css/i/iiwvrybnk.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGvo2rAduP"><g class="aql7dnt-u"><path class="e6x_babbs"/><path class="iiwvrybnk"/></g></mask></defs><path mask="url(#SVGvo2rAduP)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:magnet" /></template>
