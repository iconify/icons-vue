<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qvnkdr6kn.css';
import '../../css/u/ufqy7fo2b.css';
import '../../css/w/wvnrybc8p.css';
import '../../css/a/azzi7-0in.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="qvnkdr6kn"/><path class="ufqy7fo2b"/><path class="wvnrybc8p"/><path class="azzi7-0in"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fxemoji:circledideographsecret" /></template>
