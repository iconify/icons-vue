<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kip_gc83p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kip_gc83p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:book-up-filled" /></template>
