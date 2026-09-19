<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs9da2b6b.css';
import '../../css/r/rc1e9pbso.css';
import '../../css/j/j_v36pbuz.css';
import '../../css/g/gnte2wbni.css';
import '../../css/c/ch-mh8b7w.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 fs9da2b6b"/><path class="clr-i-outline clr-i-outline-path-2 rc1e9pbso"/><path class="clr-i-outline clr-i-outline-path-3 j_v36pbuz"/><path class="clr-i-outline clr-i-outline-path-4 gnte2wbni"/><path class="ch-mh8b7w clr-i-outline clr-i-outline-path-5"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:disconnected-line" /></template>
