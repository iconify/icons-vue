<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aynqz1gse.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="aynqz1gse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:keyboard-off-filled" /></template>
