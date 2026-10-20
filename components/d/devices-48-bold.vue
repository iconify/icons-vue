<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wxv9cpb_s.css';
import '../../css/l/lsq14_blx.css';
import '../../css/m/m603dbbqf.css';
import '../../css/l/lt1ufjbwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wxv9cpb_s"/><path class="lsq14_blx"/><path class="m603dbbqf"/><path class="lt1ufjbwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:devices-48-bold" /></template>
