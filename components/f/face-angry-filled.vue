<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cgqhi0q5m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cgqhi0q5m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:face-angry-filled" /></template>
