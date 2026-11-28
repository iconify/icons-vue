<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu-2u4b_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fu-2u4b_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:dice-5" /></template>
