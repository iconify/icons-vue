<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wfth-yblq.css';
import '../../css/y/yzsp5cclf.css';
import '../../css/u/u6upu__6m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wfth-yblq"/><path class="yzsp5cclf"/><path class="u6upu__6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gcp:datapol" /></template>
