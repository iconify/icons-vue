<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/k8v9elbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k8v9elbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:handheld-alt-2-filled" /></template>
