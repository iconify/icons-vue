<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z6zkfm9wf.css';
import '../../css/r/rzyvrkbci.css';
import '../../css/n/no05bkayi.css';
import '../../css/r/rj8pwo61t.css';
import '../../css/h/hq6hy3pct.css';
import '../../css/j/j3n2_bb5y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z6zkfm9wf"/><path class="rzyvrkbci"/><path class="no05bkayi"/><path class="rj8pwo61t"/><path class="hq6hy3pct"/><path class="j3n2_bb5y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:e-bike-charging-20" /></template>
