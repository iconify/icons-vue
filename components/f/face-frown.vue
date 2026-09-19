<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xgrpurb3m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xgrpurb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:face-frown" /></template>
