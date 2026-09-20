<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pw-s8tbiq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pw-s8tbiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:bluetooth" /></template>
