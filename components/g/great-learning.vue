<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qwv2phcpn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qwv2phcpn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:great-learning" /></template>
