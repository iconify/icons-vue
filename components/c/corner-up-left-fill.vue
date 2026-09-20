<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqn-pgrxp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqn-pgrxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:corner-up-left-fill" /></template>
