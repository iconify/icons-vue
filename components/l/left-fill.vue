<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wj96fvbes.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wj96fvbes"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:left-fill" /></template>
