<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l80swbbpu.css';
import '../../css/x/x8j868biu.css';
import '../../css/d/dkuxko7-l.css';
import '../../css/s/s9svr0ewr.css';
import '../../css/k/ksj_fcbxc.css';
import '../../css/r/rbm6z8bcb.css';
import '../../css/b/byj62vblb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l80swbbpu wm-shadow"/><path class="x8j868biu"/><path class="dkuxko7-l"/><path class="s9svr0ewr"/><path class="ksj_fcbxc"/><path class="rbm6z8bcb wm-shine"/><path class="byj62vblb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-plush:chevron-left" /></template>
