<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/x/xzkp8w4-s.css';
import '../../css/q/qc6zml-vw.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGr1BG7bpF"><g class="v3_i3wktz"><path class="xzkp8w4-s"/><path class="qc6zml-vw"/></g></mask></defs><path mask="url(#SVGr1BG7bpF)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:experiment-one" /></template>
