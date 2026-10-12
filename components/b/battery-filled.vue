<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i-zz2fp3p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i-zz2fp3p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:battery-filled" /></template>
