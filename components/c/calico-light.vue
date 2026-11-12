<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp79mfbbx.css';
import '../../css/w/wkurt-npl.css';
import '../../css/g/gk6duor4d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kp79mfbbx"/><path class="wkurt-npl"/><path class="gk6duor4d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:calico-light" /></template>
