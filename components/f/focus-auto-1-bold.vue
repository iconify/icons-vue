<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qaitsdb2b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qaitsdb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:focus-auto-1-bold" /></template>
