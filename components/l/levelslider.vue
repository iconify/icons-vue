<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uj11_sb5g.css';
import '../../css/g/g0irkt0rl.css';
import '../../css/i/ikh3n7nzg.css';
import '../../css/m/mn5jq8ovs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uj11_sb5g"/><path class="g0irkt0rl"/><path class="ikh3n7nzg"/><path class="mn5jq8ovs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:levelslider" /></template>
