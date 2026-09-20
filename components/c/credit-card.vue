<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upbpp921n.css';
import '../../css/k/k-g2zcgtu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="upbpp921n"/><path class="k-g2zcgtu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:credit-card" /></template>
