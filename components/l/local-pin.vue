<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/y/y7ic1bu-x.css';
import '../../css/o/ok5knhbhc.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4WajydOT"><g class="v3_i3wktz"><path class="y7ic1bu-x"/><path class="ok5knhbhc"/></g></mask></defs><path mask="url(#SVG4WajydOT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:local-pin" /></template>
