<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l-x4ojbyc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l-x4ojbyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:clock-arrow-down-sharp" /></template>
