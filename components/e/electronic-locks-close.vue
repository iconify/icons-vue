<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/c/c6pd6mb5r.css';
import '../../css/g/g193ptbsc.css';
import '../../css/n/n3pzp0m4r.css';
import '../../css/b/bv8fg4gct.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGkePhIc2C"><g class="ufeehvblu"><rect class="c6pd6mb5r"/><path class="g193ptbsc"/><path class="n3pzp0m4r"/><path class="bv8fg4gct"/></g></mask></defs><path mask="url(#SVGkePhIc2C)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:electronic-locks-close" /></template>
