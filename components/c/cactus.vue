<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyfe__5ov.css';
import '../../css/i/izee4xbjj.css';
import '../../css/t/tdt98o_hr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jyfe__5ov"/><path class="izee4xbjj"/><path class="tdt98o_hr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:cactus" /></template>
