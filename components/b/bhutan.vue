<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyk1s6ipo.css';
import '../../css/a/alb5d4f2o.css';
import '../../css/m/mar76sscm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":30,"height":24};
const content = `<path class="cyk1s6ipo"/><path class="alb5d4f2o"/><path class="mar76sscm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler-flags:bhutan" /></template>
