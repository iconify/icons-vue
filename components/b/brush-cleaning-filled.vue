<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9uy09baq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="h9uy09baq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:brush-cleaning-filled" /></template>
