<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hv0oiobzm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hv0oiobzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:kraken" /></template>
