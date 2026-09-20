<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6gn4b3ev.css';
import '../../css/q/qbrse918c.css';
import '../../css/p/pr7mw8ssc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="t6gn4b3ev"/><path class="qbrse918c"/><path class="pr7mw8ssc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:anchr" /></template>
