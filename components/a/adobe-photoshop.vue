<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ctl9dy8me.css';
import '../../css/k/kq3mrbcfj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="ctl9dy8me"/><path class="kq3mrbcfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:adobe-photoshop" /></template>
