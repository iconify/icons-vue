<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cy5gilhhu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cy5gilhhu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:app-window-filled" /></template>
