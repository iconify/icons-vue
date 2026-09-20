<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbcomfbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbcomfbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:fast-mail-alt" /></template>
