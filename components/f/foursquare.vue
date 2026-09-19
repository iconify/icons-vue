<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/i/iu4u_pbnw.css';
import '../../css/b/bstxvf1ow.css';
import '../../css/m/mk32x5a4i.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGd6h938W"><g class="wwvp95byt"><path class="iu4u_pbnw"/><path class="bstxvf1ow"/><path class="mk32x5a4i"/></g></mask></defs><path mask="url(#SVGGd6h938W)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:foursquare" /></template>
