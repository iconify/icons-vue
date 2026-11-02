<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7fev4-_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7fev4-_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:git-merge-2-line" /></template>
