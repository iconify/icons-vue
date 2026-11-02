<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lm5ip2blu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lm5ip2blu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:command-fill" /></template>
