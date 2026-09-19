<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yru16-bfy.css';
import '../../css/e/euuh9f3mr.css';
import '../../css/j/jlo745u3w.css';
import '../../css/z/zum5gdayo.css';
import '../../css/n/nd86j5_sb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="yru16-bfy"/><circle class="euuh9f3mr"/><path class="jlo745u3w"/><path class="zum5gdayo"/><path class="nd86j5_sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:leftmagnifyingglass" /></template>
