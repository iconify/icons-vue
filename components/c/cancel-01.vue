<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z23r0f8ry.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z23r0f8ry"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:cancel-01" /></template>
