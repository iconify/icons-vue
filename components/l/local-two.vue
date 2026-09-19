<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/u/ucv-pibjs.css';
import '../../css/c/co9te6vwq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdKRUdeVA"><g class="ufeehvblu"><path class="ucv-pibjs"/><path class="co9te6vwq"/></g></mask></defs><path mask="url(#SVGdKRUdeVA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:local-two" /></template>
