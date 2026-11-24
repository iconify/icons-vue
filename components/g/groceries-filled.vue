<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewqblsbzq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ewqblsbzq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:groceries-filled" /></template>
