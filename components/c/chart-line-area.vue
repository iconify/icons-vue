<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/o/oan152bkl.css';
import '../../css/v/v3sybybfr.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGG6xKxdRX"><g class="v3_i3wktz"><path class="oan152bkl"/><path class="v3sybybfr"/></g></mask></defs><path mask="url(#SVGG6xKxdRX)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:chart-line-area" /></template>
