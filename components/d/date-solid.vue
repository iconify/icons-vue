<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhe3ibclx.css';
import '../../css/b/b54bhv41g.css';
import '../../css/w/wftjatb3x.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-solid clr-i-solid-path-1 mhe3ibclx"/><path class="b54bhv41g clr-i-solid clr-i-solid-path-2"/><path class="clr-i-solid clr-i-solid-path-3 wftjatb3x"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:date-solid" /></template>
