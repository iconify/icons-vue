<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g01q5um2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g01q5um2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:dock-top-right-alt-filled" /></template>
