<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oxb_yw1vz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oxb_yw1vz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-from-left-filled" /></template>
