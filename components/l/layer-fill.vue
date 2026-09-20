<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zs4pc5mry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zs4pc5mry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:layer-fill" /></template>
