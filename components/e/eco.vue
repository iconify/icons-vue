<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cu-3omdxe.css';
import '../../css/q/qjqgoubck.css';
import '../../css/b/bp_58fjhm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cu-3omdxe"/><path class="qjqgoubck"/><path class="bp_58fjhm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:eco" /></template>
