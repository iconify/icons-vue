<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kqv9-8b0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kqv9-8b0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:copyright-filled" /></template>
