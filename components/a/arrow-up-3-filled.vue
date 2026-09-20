<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gxarz0beq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gxarz0beq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-up-3-filled" /></template>
