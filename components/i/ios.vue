<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdx9_ybpf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kdx9_ybpf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:ios" /></template>
