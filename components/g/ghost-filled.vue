<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ao6xx6nbg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ao6xx6nbg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ghost-filled" /></template>
