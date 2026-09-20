<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_stj679q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24,"left":-5,"top":-3};
const content = `<path class="x_stj679q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="jam:chronometer-f" /></template>
