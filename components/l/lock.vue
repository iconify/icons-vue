<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/r/rm2v37f1t.css';
import '../../css/h/h39g81kyw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGUQZeRbnh"><g class="v3_i3wktz"><rect class="rm2v37f1t"/><path class="h39g81kyw"/></g></mask></defs><path mask="url(#SVGUQZeRbnh)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:lock" /></template>
