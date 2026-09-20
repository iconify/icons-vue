<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ic8rdibgp.css';
import '../../css/x/xrb5f7bdm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="ic8rdibgp"/><path class="xrb5f7bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ecowitt" /></template>
