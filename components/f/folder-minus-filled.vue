<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kgio3ubzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kgio3ubzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:folder-minus-filled" /></template>
