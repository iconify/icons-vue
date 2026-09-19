<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/g/gnens_cuk.css';
import '../../css/n/n0tohdbyd.css';
import '../../css/f/fz171i7ps.css';
import '../../css/z/zv7vgacil.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGaJOJcZjJ"><g class="ufeehvblu"><path class="gnens_cuk"/><path class="n0tohdbyd"/><path class="fz171i7ps"/><path class="zv7vgacil"/></g></mask></defs><path mask="url(#SVGaJOJcZjJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:broadcast-radio" /></template>
