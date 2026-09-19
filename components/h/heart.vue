<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t6e7blb4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t6e7blb4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bxs:heart" /></template>
