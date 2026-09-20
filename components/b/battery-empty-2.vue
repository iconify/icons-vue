<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6uu00ymn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x6uu00ymn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:battery-empty-2" /></template>
