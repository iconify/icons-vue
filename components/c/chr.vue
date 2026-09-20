<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/euz4yigix.css';
import '../../css/x/xrxfll02s.css';
import '../../css/p/p5so3dbgl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="euz4yigix"/><path class="xrxfll02s"/><path class="p5so3dbgl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:chr" /></template>
