<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kf3e5ykvo.css';
import '../../css/b/brzn_0bpr.css';
import '../../css/w/wplkh7x2z.css';
import '../../css/z/zsll00blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="kf3e5ykvo"/><g class="brzn_0bpr"><circle class="wplkh7x2z"/><path class="zsll00blu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:disappointed-face" /></template>
