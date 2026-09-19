<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mxc6vr24n.css';
import '../../css/l/lc94xtz6s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<circle class="mxc6vr24n"/><path class="lc94xtz6s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxs-camera-home" /></template>
