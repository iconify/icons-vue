<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec4i1g93h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ec4i1g93h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:circle-fading-plus" /></template>
