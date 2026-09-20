<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dg15ygnub.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dg15ygnub"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:lock-unlocked-bold" /></template>
