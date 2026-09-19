<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pw_3lzbwf.css';
import '../../css/l/l53sk5-jo.css';
import '../../css/g/gcrw_6box.css';
import '../../css/z/zevwslsun.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGK1sGAdZd"><g class="ft5dv1b6b"><path class="pw_3lzbwf"/><path class="l53sk5-jo"/><path class="gcrw_6box"/><path class="zevwslsun"/></g></mask></defs><path mask="url(#SVGK1sGAdZd)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:file-display-one" /></template>
