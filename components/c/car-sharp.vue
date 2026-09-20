<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx4o6tq-j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jx4o6tq-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-sharp" /></template>
