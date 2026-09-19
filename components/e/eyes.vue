<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/l/lftmmacng.css';
import '../../css/k/karz80bzc.css';
import '../../css/a/a3fv3hq-a.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGPcxoUced"><g class="s9cl3zbei"><path clip-rule="evenodd" class="lftmmacng"/><path class="karz80bzc"/><path class="a3fv3hq-a"/></g></mask></defs><path mask="url(#SVGPcxoUced)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:eyes" /></template>
