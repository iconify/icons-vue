<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mhtd2p4aa.css';
import '../../css/f/flgomrbzx.css';
import '../../css/q/qh3-d7bck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="mhtd2p4aa"/><path class="flgomrbzx"/><path class="qh3-d7bck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:credit-card-check-20" /></template>
