<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/z/z6l2x0pwq.css';
import '../../css/f/fr5macbyd.css';
import '../../css/s/sl_g-c3zu.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGHpfRzeTP"><g class="v3_i3wktz"><path class="z6l2x0pwq"/><path class="fr5macbyd"/><path class="sl_g-c3zu"/></g></mask></defs><path mask="url(#SVGHpfRzeTP)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:dropbox" /></template>
