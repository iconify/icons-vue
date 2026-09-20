<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vl0knccre.css';
import '../../css/i/iqt0h4b6a.css';
import '../../css/x/xncxpgo4a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vl0knccre"/><path class="iqt0h4b6a"/><path class="xncxpgo4a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-pixel:interface-essential-link" /></template>
