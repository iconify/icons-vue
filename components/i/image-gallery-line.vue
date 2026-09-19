<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m1bi21wia.css';
import '../../css/a/a43pamegb.css';
import '../../css/k/kav-r5h5b.css';
import '../../css/b/bcpzljbeb.css';
import '../../css/j/jn9mjsb2g.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 m1bi21wia"/><path class="a43pamegb clr-i-outline clr-i-outline-path-2"/><path class="clr-i-outline clr-i-outline-path-3 kav-r5h5b"/><path class="bcpzljbeb clr-i-outline clr-i-outline-path-4"/><path class="clr-i-outline clr-i-outline-path-5 jn9mjsb2g"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:image-gallery-line" /></template>
