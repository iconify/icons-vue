<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/av7qmjbdc.css';
import '../../css/x/xnlpiqbcd.css';
import '../../css/v/vc3m3pbaa.css';
import '../../css/j/jysb2bbxh.css';
import '../../css/q/q75ztzbgi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="av7qmjbdc"/><path class="xnlpiqbcd"/><path class="vc3m3pbaa"/><path class="jysb2bbxh"/><path class="q75ztzbgi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:automatic1111-dark" /></template>
