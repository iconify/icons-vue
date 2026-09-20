<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vrmuud_5g.css';
import '../../css/l/lcyii6bqn.css';
import '../../css/x/x2yq7dqap.css';
import '../../css/b/bku-i3w6b.css';
import '../../css/o/otianebdo.css';
import '../../css/r/rrpz0cwhx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="vrmuud_5g"><path class="lcyii6bqn"/><path class="x2yq7dqap"/></g><path class="bku-i3w6b"/><path class="otianebdo"/><path class="rrpz0cwhx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:fusion-360" /></template>
