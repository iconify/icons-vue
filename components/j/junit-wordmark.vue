<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zl5yxuxbb.css';
import '../../css/q/qpw537-7f.css';
import '../../css/o/omvhn6b9p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zl5yxuxbb"/><path class="qpw537-7f"/><path class="omvhn6b9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:junit-wordmark" /></template>
