<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/e/ezq-zbd4q.css';
import '../../css/v/vqp_12z-l.css';
import '../../css/d/dvv2aacke.css';
import '../../css/y/ycjmwhbod.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGXmaTpHA"><g class="ufeehvblu"><path class="ezq-zbd4q"/><path class="vqp_12z-l"/><path class="dvv2aacke"/><path class="ycjmwhbod"/></g></mask></defs><path mask="url(#SVGGXmaTpHA)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:mail-review" /></template>
