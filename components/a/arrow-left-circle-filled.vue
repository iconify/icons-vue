<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fz_5soocm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fz_5soocm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-left-circle-filled" /></template>
