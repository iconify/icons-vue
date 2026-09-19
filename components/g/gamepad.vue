<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/smucxhg_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="smucxhg_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:gamepad" /></template>
