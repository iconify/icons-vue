<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t-ki4cbhf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-ki4cbhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:hot-tub-filled" /></template>
