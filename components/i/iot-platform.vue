<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gac48jb7z.css';
import '../../css/n/n_m9vgi5i.css';
import '../../css/r/r48c3wd-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="gac48jb7z"/><path class="n_m9vgi5i"/><path class="r48c3wd-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:iot-platform" /></template>
