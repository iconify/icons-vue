<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u1ljx3b6b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1ljx3b6b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:fever" /></template>
