<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mt5z90bty.css';
import '../../css/r/r7co23qft.css';
import '../../css/w/wpnqak87z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="mt5z90bty"/><path class="r7co23qft"/><path class="wpnqak87z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:ios-code-download" /></template>
