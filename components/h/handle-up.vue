<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/v/vcum2uxal.css';
import '../../css/q/qfy4gx9pp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgJVf2ezG"><g class="ufeehvblu"><rect class="vcum2uxal"/><path class="qfy4gx9pp"/></g></mask></defs><path mask="url(#SVGgJVf2ezG)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:handle-up" /></template>
