<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iw8qkhr5t.css';
import '../../css/w/wt0hjgbht.css';
import '../../css/k/kuycmfbxw.css';
import '../../css/a/aljyvwb8e.css';
import '../../css/h/hv37hybeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="iw8qkhr5t"/><path class="wt0hjgbht"/><path class="kuycmfbxw"/><path class="aljyvwb8e"/><path class="hv37hybeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:first-aid-bag" /></template>
