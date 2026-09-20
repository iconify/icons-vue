<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c5n_u8bzw.css';
import '../../css/x/xxv9ffbbv.css';
import '../../css/k/kfcvyebwh.css';
import '../../css/h/hnt58cbem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="c5n_u8bzw"/><path class="xxv9ffbbv"/><path class="kfcvyebwh"/><path class="hnt58cbem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:apache" /></template>
