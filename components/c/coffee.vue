<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kfujh6bma.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kfujh6bma"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:coffee" /></template>
