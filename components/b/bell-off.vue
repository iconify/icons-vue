<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/akkca56wk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="akkca56wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:bell-off" /></template>
