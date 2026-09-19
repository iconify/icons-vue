<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/b/bqzj_jbnn.css';
import '../../css/s/s51uqybkz.css';
import '../../css/q/qmo-ysovi.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlYaKVb2W"><g class="v3_i3wktz"><path class="bqzj_jbnn"/><path class="s51uqybkz"/><path class="qmo-ysovi"/></g></mask></defs><path mask="url(#SVGlYaKVb2W)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:add-music" /></template>
