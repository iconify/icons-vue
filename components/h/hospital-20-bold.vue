<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qrrp2vb9e.css';
import '../../css/i/iaidsl54n.css';
import '../../css/g/gvfs-1b3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qrrp2vb9e"/><path class="iaidsl54n"/><path class="gvfs-1b3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:hospital-20-bold" /></template>
