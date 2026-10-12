<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b8f82y98i.css';
import '../../css/i/i23da44dj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b8f82y98i"/><path class="i23da44dj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:lighthouse-filled" /></template>
