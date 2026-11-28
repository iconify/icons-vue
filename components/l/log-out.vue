<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lgj84yb6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lgj84yb6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:log-out" /></template>
