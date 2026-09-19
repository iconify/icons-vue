<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbdjsbbdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbdjsbbdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:lock-open-filled" /></template>
