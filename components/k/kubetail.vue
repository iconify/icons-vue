<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uqcszbc6x.css';
import '../../css/e/ety_7rmqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="uqcszbc6x"/><path class="ety_7rmqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:kubetail" /></template>
