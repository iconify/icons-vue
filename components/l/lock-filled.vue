<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d5gtbrjwq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d5gtbrjwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:lock-filled" /></template>
