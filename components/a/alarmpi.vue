<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o12gz742v.css';
import '../../css/s/sl76bhbtp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<circle class="o12gz742v"/><path class="sl76bhbtp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:alarmpi" /></template>
