<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ks4-i1l3x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ks4-i1l3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:image-filled" /></template>
