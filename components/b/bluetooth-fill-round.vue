<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bi2fi3bkp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi2fi3bkp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bluetooth-fill-round" /></template>
