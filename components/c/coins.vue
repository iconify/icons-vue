<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lmezu1bij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lmezu1bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:coins" /></template>
