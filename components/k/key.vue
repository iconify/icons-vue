<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ku8abw8kk.css';
import '../../css/h/h2mu3-bvk.css';
import '../../css/n/nd04x3bmn.css';
import '../../css/b/b4dxp4bhi.css';
import '../../css/u/uy7dsmi8p.css';
import '../../css/j/j8qz-1b3t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ku8abw8kk wm-shadow"/><path class="h2mu3-bvk wm-k"/><path class="nd04x3bmn wm-k"/><path class="b4dxp4bhi wm-k"/><path class="uy7dsmi8p wm-k"/><path class="j8qz-1b3t wm-shine"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-pastel:key" /></template>
