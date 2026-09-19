<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wzjqs1bbd.css';
import '../../css/l/l4h5u_zeh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wzjqs1bbd"/><path class="l4h5u_zeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:file-tray-full-outline" /></template>
