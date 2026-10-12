<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pp1g86hto.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pp1g86hto"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-down-filled" /></template>
