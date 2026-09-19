<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ys-ce1bfu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ys-ce1bfu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:camping" /></template>
