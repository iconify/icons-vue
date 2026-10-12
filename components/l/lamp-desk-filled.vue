<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b7tvawbir.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b7tvawbir"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:lamp-desk-filled" /></template>
