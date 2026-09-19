<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l4afgeb-d.css';
import '../../css/v/v1z4zvbtf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l4afgeb-d"/><path class="v1z4zvbtf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:calculator" /></template>
