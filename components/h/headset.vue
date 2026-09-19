<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2iu8cnhj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="l2iu8cnhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:headset" /></template>
