<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy9pkxbbs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cy9pkxbbs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:haze-filled" /></template>
