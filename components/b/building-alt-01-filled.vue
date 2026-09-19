<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yn7ht-b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yn7ht-b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:building-alt-01-filled" /></template>
