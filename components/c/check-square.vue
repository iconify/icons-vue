<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6_rr0b0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6_rr0b0a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uit:check-square" /></template>
