<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dyp4fxbhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dyp4fxbhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:flask-round-filled" /></template>
