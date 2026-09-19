<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up41n5_fe.css';
import '../../css/y/yb5y__l1h.css';
import '../../css/x/x8dhmccog.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="up41n5_fe"/><path class="yb5y__l1h"/><path class="x8dhmccog"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:logo-electron" /></template>
