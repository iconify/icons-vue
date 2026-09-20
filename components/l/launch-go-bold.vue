<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/javv36f_m.css';
import '../../css/s/s44bm75jf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="javv36f_m"/><path class="s44bm75jf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:launch-go-bold" /></template>
