<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xq3l0ci3a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq3l0ci3a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:gameboy3-filled" /></template>
