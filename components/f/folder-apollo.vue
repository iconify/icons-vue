<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6_kf7bqk.css';
import '../../css/c/cc8cr8bjt.css';
import '../../css/c/c46-9_ypa.css';
import '../../css/n/n1ppsob_d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="l6_kf7bqk"/><g class="cc8cr8bjt"><path class="c46-9_ypa"/><path class="n1ppsob_d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:folder-apollo" /></template>
