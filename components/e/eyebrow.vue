<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/b/b8jxfhb0t.css';
import '../../css/k/k-eaexmhb.css';
import '../../css/n/nxtfqrbmx.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGNrGRWdta"><g class="ufeehvblu"><path class="b8jxfhb0t"/><path class="k-eaexmhb"/><path class="nxtfqrbmx"/></g></mask></defs><path mask="url(#SVGNrGRWdta)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:eyebrow" /></template>
