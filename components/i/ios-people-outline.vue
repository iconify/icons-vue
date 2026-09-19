<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/boiwm4w4j.css';
import '../../css/t/tm6rd794g.css';
import '../../css/k/k3t8hmbrn.css';
import '../../css/n/nxn8obbav.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="boiwm4w4j"/><path class="tm6rd794g"/><path class="k3t8hmbrn"/><path class="nxn8obbav"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-people-outline" /></template>
