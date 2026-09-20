<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s0m8trbfm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s0m8trbfm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:car-3-bold" /></template>
