<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y3bww6big.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"top":-4};
const content = `<path class="y3bww6big"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:gamepad-f" /></template>
