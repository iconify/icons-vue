<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmxpybrsb.css';
import '../../css/n/nghpb3cka.css';
import '../../css/u/uq14z1bmm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmxpybrsb"/><path class="nghpb3cka"/><path class="uq14z1bmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:feed-bold-duotone" /></template>
