<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l3_uaza_u.css';
import '../../css/z/zn4yv5btu.css';
import '../../css/t/tdsy3x63e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l3_uaza_u"/><path clip-rule="evenodd" class="zn4yv5btu"/><path clip-rule="evenodd" class="tdsy3x63e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:export-filled" /></template>
