<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxc6vr24n.css';
import '../../css/s/sor5e_3vz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="mxc6vr24n"/><path class="sor5e_3vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:camera-home" /></template>
