<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/lgjt7sb2t.css';
import '../../css/g/g9vxsgblh.css';
import '../../css/e/e7544v40j.css';
import '../../css/m/mxy1xab9g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="lgjt7sb2t wm-shadow"/><path class="g9vxsgblh wm-shadow"/><path class="e7544v40j"/><path class="mxy1xab9g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-brutal:inbox" /></template>
