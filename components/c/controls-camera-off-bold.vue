<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn_ovn4eq.css';
import '../../css/j/jm-sdob1r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn_ovn4eq"/><path class="jm-sdob1r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:controls-camera-off-bold" /></template>
