<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zojmpb3mi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zojmpb3mi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:bracket-arrow-up" /></template>
