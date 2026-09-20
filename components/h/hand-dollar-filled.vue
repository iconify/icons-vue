<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixyvvha0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixyvvha0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:hand-dollar-filled" /></template>
