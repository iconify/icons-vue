<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp79mfbbx.css';
import '../../css/l/lcqrf1bec.css';
import '../../css/s/sr4sabbve.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kp79mfbbx"/><path class="lcqrf1bec"/><path class="sr4sabbve"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:calico-light" /></template>
