<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ue4v1ubkz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ue4v1ubkz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:lock" /></template>
