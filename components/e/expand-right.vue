<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/x/x16illbqh.css';
import '../../css/e/egt6m3bbv.css';
import '../../css/b/bq41sjbfa.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGfkXvWiBU"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="x16illbqh"/><path class="egt6m3bbv"/><path class="bq41sjbfa"/></g></mask></defs><path mask="url(#SVGfkXvWiBU)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:expand-right" /></template>
