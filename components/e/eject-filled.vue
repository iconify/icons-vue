<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fbfztel_k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fbfztel_k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:eject-filled" /></template>
