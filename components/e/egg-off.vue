<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk_gojgqk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rk_gojgqk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:egg-off" /></template>
