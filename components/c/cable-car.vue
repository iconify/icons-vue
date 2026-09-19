<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/l/ld_enacku.css';
import '../../css/n/nwdlh3bmk.css';
import '../../css/s/sv_i3rb-p.css';
import '../../css/f/fc40hdc0c.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGTGGKJeuT"><g class="s9cl3zbei"><path class="ld_enacku"/><path class="nwdlh3bmk"/><path class="sv_i3rb-p"/><path class="fc40hdc0c"/></g></mask></defs><path mask="url(#SVGTGGKJeuT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:cable-car" /></template>
