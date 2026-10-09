<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jr8phfb8h.css';
import '../../css/u/uyuy9qbxm.css';
import '../../css/v/vfxz7qx3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="jr8phfb8h"/><path class="uyuy9qbxm"/><path class="vfxz7qx3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:headset-48-bold" /></template>
