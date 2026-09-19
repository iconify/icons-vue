<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wejjyi8fq.css';
import '../../css/i/im3c3rjxf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="wejjyi8fq"/><path class="im3c3rjxf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-wallet" /></template>
