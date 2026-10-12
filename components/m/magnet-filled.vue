<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m6sfktb2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="m6sfktb2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:magnet-filled" /></template>
