<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgrtu-b6i.css';
import '../../css/n/nq7uy796s.css';
import '../../css/g/gfmzq89ku.css';
import '../../css/x/x073nxb-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qgrtu-b6i"/><path class="nq7uy796s"/><path class="gfmzq89ku"/><path class="x073nxb-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:campsite-48" /></template>
