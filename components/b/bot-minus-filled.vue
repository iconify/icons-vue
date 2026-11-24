<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdj0_9ype.css';
import '../../css/g/ge98ujwjz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kdj0_9ype"/><path class="ge98ujwjz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bot-minus-filled" /></template>
