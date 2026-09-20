<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tf7inyggn.css';
import '../../css/j/jkq7-hbwz.css';
import '../../css/b/bl09rcbev.css';
import '../../css/p/ph-mjcb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="tf7inyggn"/><path class="jkq7-hbwz"/><path class="bl09rcbev"/><path class="ph-mjcb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:bavaria-flag" /></template>
