<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x-6wqibix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="x-6wqibix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-up-filled" /></template>
