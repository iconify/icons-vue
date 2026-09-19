<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/n/nvjxntb_m.css';
import '../../css/f/fopngibfa.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGzW6Fdctb"><g class="v3_i3wktz"><path class="nvjxntb_m"/><path class="fopngibfa"/></g></mask></defs><path mask="url(#SVGzW6Fdctb)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:insert-card" /></template>
