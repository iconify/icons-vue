<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m5pl09c9y.css';
import '../../css/c/c-h7mvgqw.css';
import '../../css/n/nxeytq4fz.css';
import '../../css/n/n30k5ibrs.css';
import '../../css/m/m2o3sh-9c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="clr-i-outline clr-i-outline-path-1 m5pl09c9y"/><path class="c-h7mvgqw clr-i-outline clr-i-outline-path-2"/><path class="clr-i-outline clr-i-outline-path-3 nxeytq4fz"/><path class="clr-i-outline clr-i-outline-path-4 n30k5ibrs"/><path class="m2o3sh-9c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="clarity:chat-bubble-line" /></template>
