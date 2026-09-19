<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnl1p-2gq.css';
import '../../css/l/llymw2wsd.css';
import '../../css/s/slx--zbzd.css';
import '../../css/l/loxcckgkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="qnl1p-2gq"/><path class="llymw2wsd"/><path class="slx--zbzd"/><path class="loxcckgkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-images" /></template>
