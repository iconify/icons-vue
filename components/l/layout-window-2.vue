<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lkovylnqj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkovylnqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:layout-window-2" /></template>
