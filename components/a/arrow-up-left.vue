<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/ljdnzhb7i.css';
import '../../css/i/i0euaobek.css';
import '../../css/c/ciy208bii.css';
import '../../css/j/j9ot3x1rq.css';
import '../../css/y/y5dde6imt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="ljdnzhb7i wm-deco"/><path class="i0euaobek wm-k"/><path class="ciy208bii wm-k"/><path class="j9ot3x1rq wm-k"/><path class="wm-shine y5dde6imt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-anime:arrow-up-left" /></template>
