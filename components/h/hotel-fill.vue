<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh0f9ob6v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kh0f9ob6v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:hotel-fill" /></template>
