<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ar2wz1o0x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="ar2wz1o0x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:bus-11" /></template>
