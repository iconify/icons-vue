<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ojjtxm8cz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ojjtxm8cz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:glass-water-filled" /></template>
