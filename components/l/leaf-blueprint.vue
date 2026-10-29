<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/r/r36q9z2wp.css';
import '../../css/o/o0ghn90ei.css';
import '../../css/i/i91bbbg-m.css';
import '../../css/v/vttpfcc7k.css';
import '../../css/v/vg_w0kzln.css';
import '../../css/b/b86m5ybhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="r36q9z2wp wm-deco"/><path class="o0ghn90ei wm-deco"/><path class="i91bbbg-m wm-deco"/><path class="vttpfcc7k wm-k"/><path class="vg_w0kzln wm-a"/><path class="b86m5ybhz wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:leaf-blueprint" /></template>
