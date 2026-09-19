<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/w/wtoa8cbyq.css';
import '../../css/l/l3uh-do_m.css';
import '../../css/d/d_lsnlbdq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8HfSBbvJ"><g class="s9cl3zbei"><path class="wtoa8cbyq"/><path class="l3uh-do_m"/><path class="d_lsnlbdq"/></g></mask></defs><path mask="url(#SVG8HfSBbvJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:facial-mask" /></template>
