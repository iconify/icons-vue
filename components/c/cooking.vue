<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/f/fz_tw8bkq.css';
import '../../css/a/a9e80-b5o.css';
import '../../css/j/jma92kb0t.css';
import '../../css/v/v4s_j64ti.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGx71C2dpC"><g class="s9cl3zbei"><path class="fz_tw8bkq"/><path class="a9e80-b5o"/><path class="jma92kb0t"/><path class="v4s_j64ti"/></g></mask></defs><path mask="url(#SVGx71C2dpC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:cooking" /></template>
