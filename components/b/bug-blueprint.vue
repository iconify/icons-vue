<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/a/ac7w1hb7f.css';
import '../../css/w/wfl8tvbzr.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/l/louq1sjgq.css';
import '../../css/i/izvj3goyw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="ac7w1hb7f wm-deco"/><path class="wfl8tvbzr wm-deco"/><path class="cf3uzcrzx wm-deco"/><path class="louq1sjgq wm-k"/><path class="izvj3goyw wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:bug-blueprint" /></template>
