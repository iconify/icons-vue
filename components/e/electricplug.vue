<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbvjs_2tm.css';
import '../../css/s/s_phngbxd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="sbvjs_2tm"/><path class="s_phngbxd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:electricplug" /></template>
