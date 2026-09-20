<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2c8r3w-d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l2c8r3w-d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hierarchy2" /></template>
