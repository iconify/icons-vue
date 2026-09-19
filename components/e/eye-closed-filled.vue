<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cyj01ccef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cyj01ccef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:eye-closed-filled" /></template>
