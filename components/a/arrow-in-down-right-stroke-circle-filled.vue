<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rm30bdpol.css';
import '../../css/t/tvbix7bxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rm30bdpol"/><path class="tvbix7bxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:arrow-in-down-right-stroke-circle-filled" /></template>
