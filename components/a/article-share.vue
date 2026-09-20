<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qb-wvabvh.css';
import '../../css/d/d55v_x0qd.css';
import '../../css/y/yvl5yabej.css';
import '../../css/g/gkefinb2h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qb-wvabvh"/><path clip-rule="evenodd" class="d55v_x0qd"/><path class="yvl5yabej"/><path clip-rule="evenodd" class="gkefinb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:article-share" /></template>
