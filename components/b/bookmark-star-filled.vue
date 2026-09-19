<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frv3khv0m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frv3khv0m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:bookmark-star-filled" /></template>
