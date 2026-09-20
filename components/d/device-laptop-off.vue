<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewb1r_bgk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewb1r_bgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:device-laptop-off" /></template>
