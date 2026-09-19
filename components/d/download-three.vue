<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/m/m2blynbna.css';
import '../../css/n/nw5e1gb5o.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4bKJEdhG"><g class="ufeehvblu"><path class="m2blynbna"/><path class="nw5e1gb5o"/></g></mask></defs><path mask="url(#SVG4bKJEdhG)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:download-three" /></template>
