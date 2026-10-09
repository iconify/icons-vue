<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yxhse7b_h.css';
import '../../css/n/nyeck7_mh.css';
import '../../css/w/wsddmcbbh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yxhse7b_h"/><path class="nyeck7_mh"/><path class="wsddmcbbh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:gamepad-48" /></template>
