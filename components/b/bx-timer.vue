<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0hb-y1ml.css';
import '../../css/d/dn9k9z1wr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i0hb-y1ml"/><path class="dn9k9z1wr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-timer" /></template>
