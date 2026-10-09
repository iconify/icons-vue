<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5hh3ac5g.css';
import '../../css/q/q761jsrye.css';
import '../../css/g/gpknbotbu.css';
import '../../css/c/ceg2-nwwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m5hh3ac5g"/><path class="q761jsrye"/><path class="gpknbotbu"/><path class="ceg2-nwwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:battery-recycle-20" /></template>
