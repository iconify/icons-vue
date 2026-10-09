<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yc93bwpoh.css';
import '../../css/s/sc1f8rb_h.css';
import '../../css/m/mo7b8rbns.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yc93bwpoh"/><path class="sc1f8rb_h"/><path class="mo7b8rbns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:factory-emissions-48-bold" /></template>
