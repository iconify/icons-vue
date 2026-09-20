<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g-ttlzbrv.css';
import '../../css/w/woppo0l-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-ttlzbrv"/><path class="woppo0l-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:inbox" /></template>
