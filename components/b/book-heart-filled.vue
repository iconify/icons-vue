<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wkz8wob9a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wkz8wob9a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:book-heart-filled" /></template>
