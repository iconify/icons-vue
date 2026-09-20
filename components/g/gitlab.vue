<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p7b5412_q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p7b5412_q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:gitlab" /></template>
