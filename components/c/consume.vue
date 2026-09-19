<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/s/sp1hiv_iz.css';
import '../../css/b/btaqqpbbe.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGbvWtubWN"><g class="v3_i3wktz"><path class="sp1hiv_iz"/><path class="btaqqpbbe"/></g></mask></defs><path mask="url(#SVGbvWtubWN)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:consume" /></template>
