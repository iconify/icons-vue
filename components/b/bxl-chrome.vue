<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/shpzc8bzi.css';
import '../../css/e/eh3ot8boa.css';
import '../../css/y/y2zsi2bct.css';
import '../../css/f/f5mb6fbcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="shpzc8bzi"/><path class="eh3ot8boa"/><path class="y2zsi2bct"/><path class="f5mb6fbcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bxl-chrome" /></template>
