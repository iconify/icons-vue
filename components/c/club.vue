<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/djsyizbok.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="djsyizbok"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:club" /></template>
