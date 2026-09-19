<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jthx5pb9h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jthx5pb9h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:area-filled" /></template>
