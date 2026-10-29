<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqjhdlb_v.css';
import '../../css/y/ye75vbcqm.css';
import '../../css/j/jctnliumq.css';
import '../../css/l/liw58u7sh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-a yqjhdlb_v"/><path class="wm-k ye75vbcqm"/><path class="jctnliumq wm-k"/><path class="liw58u7sh wm-k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:hand-heart" /></template>
