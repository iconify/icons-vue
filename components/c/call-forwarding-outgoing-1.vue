<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mqtb8fbuf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mqtb8fbuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:call-forwarding-outgoing-1" /></template>
