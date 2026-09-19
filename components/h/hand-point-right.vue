<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5ss5zbyo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="j5ss5zbyo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-regular:hand-point-right" /></template>
