<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7q00-byg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y7q00-byg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:heading-2" /></template>
