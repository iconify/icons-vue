<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vb_9fkb4h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vb_9fkb4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:git-fork-filled" /></template>
