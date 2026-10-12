<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l94725b2v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l94725b2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bone-filled" /></template>
