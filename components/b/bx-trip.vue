<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/powe_1b0z.css';
import '../../css/s/supz4n9yl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="powe_1b0z"/><path class="supz4n9yl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bx:bx-trip" /></template>
