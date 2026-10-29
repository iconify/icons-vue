<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lbr10cbls.css';
import '../../css/p/p1s_b1bnt.css';
import '../../css/f/fumefdsvh.css';
import '../../css/w/wmpwg_b2d.css';
import '../../css/e/e7p7esbpd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lbr10cbls wm-a"/><path class="p1s_b1bnt wm-a"/><path class="fumefdsvh wm-a"/><path class="wm-k wmpwg_b2d"/><path class="e7p7esbpd wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:hotel" /></template>
