<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mwmgjbblk.css';
import '../../css/m/mmfi7hwff.css';
import '../../css/y/yo8uw-b3d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mwmgjbblk"/><path class="mmfi7hwff"/><circle class="yo8uw-b3d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:flower-outline" /></template>
