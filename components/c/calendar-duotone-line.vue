<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ukm9jj2re.css';
import '../../css/r/r5knwvbfg.css';
import '../../css/g/ga2yrzb2l.css';
import '../../css/x/xeoe4xbcq.css';
import '../../css/c/c781xr7yq.css';
import '../../css/w/w49j0rbvv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVG4O3beeXG"><g class="ukm9jj2re"><path class="r5knwvbfg"/><rect class="ga2yrzb2l"/><path class="xeoe4xbcq"/><path class="c781xr7yq"/></g></mask></defs><path mask="url(#SVG4O3beeXG)" class="w49j0rbvv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:calendar-duotone-line" /></template>
