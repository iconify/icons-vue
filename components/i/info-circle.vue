<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdm9qq6xg.css';
import '../../css/u/uuqt_yb-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdm9qq6xg"/><path class="uuqt_yb-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:info-circle" /></template>
