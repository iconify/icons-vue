<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2yz0-bpw.css';
import '../../css/g/gnrh5itid.css';
import '../../css/f/fy2_l9k3b.css';
import '../../css/n/nqfv5ob5a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="w2yz0-bpw"/><path class="gnrh5itid"/><path class="fy2_l9k3b"/><path class="nqfv5ob5a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:chalet-20" /></template>
