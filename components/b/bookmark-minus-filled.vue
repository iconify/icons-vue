<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sx8uoonkg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sx8uoonkg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bookmark-minus-filled" /></template>
