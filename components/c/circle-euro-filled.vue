<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q-rcg7b-b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="q-rcg7b-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-euro-filled" /></template>
