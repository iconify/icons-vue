<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rmz8-hbrq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rmz8-hbrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:arrow-up-square-filled" /></template>
