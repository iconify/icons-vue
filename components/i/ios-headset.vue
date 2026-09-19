<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luyue7b6t.css';
import '../../css/e/ew7h4abcs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="luyue7b6t"/><path class="ew7h4abcs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-headset" /></template>
