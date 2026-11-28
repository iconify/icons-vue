<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zifqn-b_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zifqn-b_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:globe-check" /></template>
