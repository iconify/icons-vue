<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy2utibri.css';
import '../../css/r/r7hz-1nyr.css';
import '../../css/k/ktewzwb7e.css';
import '../../css/s/switkv-0r.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline--alerted clr-i-outline-path-1--alerted jy2utibri"/><path class="clr-i-outline--alerted clr-i-outline-path-2--alerted r7hz-1nyr"/><path class="clr-i-outline--alerted clr-i-outline-path-3--alerted ktewzwb7e"/><path class="clr-i-alert clr-i-outline--alerted clr-i-outline-path-4--alerted switkv-0r"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:clock-outline-alerted" /></template>
