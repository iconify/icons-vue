<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vc557rb_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vc557rb_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:lift-in-window-closed" /></template>
