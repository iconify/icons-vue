<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bv5149b2n.css';
import '../../css/f/fc1chxb1r.css';
import '../../css/f/fhl3-hbkm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="bv5149b2n"/><path class="fc1chxb1r"/><path class="fhl3-hbkm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:ipfs-light" /></template>
