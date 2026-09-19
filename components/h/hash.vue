<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqn1kbb3l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqn1kbb3l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:hash" /></template>
