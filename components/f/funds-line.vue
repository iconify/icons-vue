<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g5l91hbbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5l91hbbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:funds-line" /></template>
