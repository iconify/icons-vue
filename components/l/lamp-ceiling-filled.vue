<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/txccpm--h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="txccpm--h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:lamp-ceiling-filled" /></template>
