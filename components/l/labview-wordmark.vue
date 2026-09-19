<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bb-_cqblp.css';
import '../../css/g/g5k8wib8i.css';
import '../../css/x/xkrt0vp1g.css';
import '../../css/g/gv0fbehgq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="bb-_cqblp"/><path class="g5k8wib8i"/><path class="xkrt0vp1g"/><path class="gv0fbehgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:labview-wordmark" /></template>
