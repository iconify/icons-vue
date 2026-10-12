<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/ws9_ski4v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ws9_ski4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:clock-3-filled" /></template>
