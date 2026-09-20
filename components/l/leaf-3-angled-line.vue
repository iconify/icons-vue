<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hn2855mwp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hn2855mwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:leaf-3-angled-line" /></template>
