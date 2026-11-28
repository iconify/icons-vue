<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zn_0xrrua.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn_0xrrua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:car-clock" /></template>
