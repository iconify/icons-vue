<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/k/ka6c5cbmx.css';
import '../../css/p/puckv5bwn.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgzUlicSd"><g class="v3_i3wktz"><path class="ka6c5cbmx"/><path clip-rule="evenodd" class="puckv5bwn"/></g></mask></defs><path mask="url(#SVGgzUlicSd)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:hand-up" /></template>
