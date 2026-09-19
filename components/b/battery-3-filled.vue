<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnpwbhbsz.css';
import '../../css/q/qou13c05m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pnpwbhbsz"/><path class="qou13c05m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:battery-3-filled" /></template>
