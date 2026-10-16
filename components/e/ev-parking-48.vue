<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x5i9cpbbm.css';
import '../../css/k/k1a5ibk1n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x5i9cpbbm"/><path class="k1a5ibk1n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:ev-parking-48" /></template>
