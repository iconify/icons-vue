<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s071-i2ck.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s071-i2ck"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:hexagon" /></template>
