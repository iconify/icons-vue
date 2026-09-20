<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_kf_eb-t.css';
import '../../css/j/jxu6cf38p.css';
import '../../css/p/p34lxkxwh.css';
import '../../css/i/i-gsmlpun.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e_kf_eb-t"/><path class="jxu6cf38p"/><path class="p34lxkxwh"/><path class="i-gsmlpun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ksuite-kdrive" /></template>
