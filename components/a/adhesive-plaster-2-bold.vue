<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q1zehub5g.css';
import '../../css/d/do_yi4-hw.css';
import '../../css/h/hyha3ublc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q1zehub5g"/><path clip-rule="evenodd" class="do_yi4-hw"/><path class="hyha3ublc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:adhesive-plaster-2-bold" /></template>
