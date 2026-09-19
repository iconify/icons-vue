<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b1hyo6bsg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b1hyo6bsg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:ard-alpha" /></template>
