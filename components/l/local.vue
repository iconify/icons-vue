<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/q/q9thrpajc.css';
import '../../css/k/kn4gnld0a.css';
import '../../css/h/h8sbx2b5d.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG902NEeSX"><g class="v3_i3wktz"><path class="q9thrpajc"/><path class="kn4gnld0a"/><path class="h8sbx2b5d"/></g></mask></defs><path mask="url(#SVG902NEeSX)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:local" /></template>
