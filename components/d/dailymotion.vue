<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kpm8a6xpl.css';
import '../../css/y/yvc722b9s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kpm8a6xpl"/><path class="yvc722b9s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:dailymotion" /></template>
