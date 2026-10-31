<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/r/rdg50d-hq.css';
import '../../css/q/qd-99mo0g.css';
import '../../css/o/o9fioyb3w.css';
import '../../css/l/ljxy4hbql.css';
import '../../css/e/ek0doz5vi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="rdg50d-hq wm-k"/><path class="qd-99mo0g wm-deco"/><path class="o9fioyb3w wm-k"/><path class="ljxy4hbql wm-k"/><path class="ek0doz5vi wm-shadow"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-valentine:baguette" /></template>
