<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9nmekbvz.css';
import '../../css/h/hmb8w9btd.css';
import '../../css/y/yrgccdbnk.css';
import '../../css/c/cf3uzcrzx.css';
import '../../css/q/qf2jt4bcl.css';
import '../../css/a/ar0r6f66r.css';
import '../../css/b/ba_wvobfo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s9nmekbvz"><path class="hmb8w9btd wm-deco"/><path class="wm-deco yrgccdbnk"/><path class="cf3uzcrzx wm-deco"/><path class="qf2jt4bcl wm-k"/><path class="ar0r6f66r wm-a"/><path class="ba_wvobfo wm-k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:landmark-blueprint" /></template>
