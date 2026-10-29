<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xag6ozbqu.css';
import '../../css/r/r8hfrupfa.css';
import '../../css/s/sdb3vkbhq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xag6ozbqu"/><path class="r8hfrupfa wm-k"/><path class="sdb3vkbhq wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:flower-sketch" /></template>
