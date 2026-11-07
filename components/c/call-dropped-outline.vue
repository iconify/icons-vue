<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l2_o7ybby.css';
import '../../css/y/yq6674bzc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="l2_o7ybby"/><path class="yq6674bzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:call-dropped-outline" /></template>
