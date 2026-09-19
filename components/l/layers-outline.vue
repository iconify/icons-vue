<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h-1tko0hh.css';
import '../../css/i/itcix3b7o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="h-1tko0hh"/><path class="itcix3b7o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:layers-outline" /></template>
