<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7ruxowru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="w7ruxowru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-letter-k-filled" /></template>
