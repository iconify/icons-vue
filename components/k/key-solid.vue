<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mj6g5_6ki.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mj6g5_6ki"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:key-solid" /></template>
