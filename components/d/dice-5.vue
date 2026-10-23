<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez92r_4pu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ez92r_4pu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:dice-5" /></template>
