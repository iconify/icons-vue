<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t4-1rtbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t4-1rtbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:avatar-frog-gloss" /></template>
