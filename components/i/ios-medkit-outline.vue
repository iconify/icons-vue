<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqm3cru9o.css';
import '../../css/u/up_x2juwn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="iqm3cru9o"/><path class="up_x2juwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-medkit-outline" /></template>
