<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb4lz6bjn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lb4lz6bjn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:crown-filled" /></template>
