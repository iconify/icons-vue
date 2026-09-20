<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jt_dcj1zc.css';
import '../../css/v/vd8fnkbgj.css';
import '../../css/i/i424kzrcq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jt_dcj1zc"/><path class="vd8fnkbgj"/><path class="i424kzrcq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:gatus" /></template>
