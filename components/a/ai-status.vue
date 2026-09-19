<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rw3u8dcyu.css';
import '../../css/s/s3bjnib6t.css';
import '../../css/j/jjnq7107s.css';
import '../../css/l/l4qq16brp.css';
import '../../css/u/uyfynbbwi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rw3u8dcyu"/><path class="s3bjnib6t"/><path class="jjnq7107s"/><path class="l4qq16brp"/><path class="uyfynbbwi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:ai-status" /></template>
