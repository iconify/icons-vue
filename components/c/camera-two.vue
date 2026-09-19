<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/y/yeoauitov.css';
import '../../css/r/r8019eblq.css';
import '../../css/o/o8g3erbdd.css';
import '../../css/w/wcqq8obof.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpg6kxPAD"><g class="ft5dv1b6b"><rect class="yeoauitov"/><path class="r8019eblq"/><circle class="o8g3erbdd"/><circle class="wcqq8obof"/></g></mask></defs><path mask="url(#SVGpg6kxPAD)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:camera-two" /></template>
