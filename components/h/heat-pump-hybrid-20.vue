<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vt8maz9hk.css';
import '../../css/f/f2c2p1hyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vt8maz9hk"/><path class="f2c2p1hyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:heat-pump-hybrid-20" /></template>
