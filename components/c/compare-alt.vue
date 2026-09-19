<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/ql0f65czi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b ql0f65czi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:compare-alt" /></template>
