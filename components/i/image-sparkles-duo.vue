<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/k30_82bht.css';
import '../../css/w/wqk9itcqr.css';
import '../../css/q/qdzstlt9t.css';
import '../../css/a/ain1tnbxt.css';
import '../../css/s/sy7kpcbuo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="k30_82bht"/><path class="wm-s wqk9itcqr"/><path class="qdzstlt9t wm-s"/><path class="ain1tnbxt"/><path class="sy7kpcbuo wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:image-sparkles-duo" /></template>
