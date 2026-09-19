<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dzcugqb3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dzcugqb3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:barn-filled" /></template>
