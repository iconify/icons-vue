<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bd_lixbqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bd_lixbqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:candy-cane-filled" /></template>
