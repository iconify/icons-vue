<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k_gwm_bba.css';
import '../../css/x/xvmas6b-z.css';
import '../../css/o/ois2n1s1o.css';
import '../../css/k/kg_t2pb7u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="k_gwm_bba"/><path class="xvmas6b-z"/><path class="ois2n1s1o"/><path class="kg_t2pb7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:internet-network-www" /></template>
