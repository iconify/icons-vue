<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mn_e35btc.css';
import '../../css/v/vtfwic-qn.css';
import '../../css/u/uqlamj4tr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mn_e35btc"/><path class="vtfwic-qn"/><circle class="uqlamj4tr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:hard-drive-outline" /></template>
