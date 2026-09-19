<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/k/kn964er2l.css';
import '../../css/z/zersuh-bf.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBmAcke5P"><g class="v3_i3wktz"><path class="kn964er2l"/><path class="zersuh-bf"/></g></mask></defs><path mask="url(#SVGBmAcke5P)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:bezier-curve" /></template>
