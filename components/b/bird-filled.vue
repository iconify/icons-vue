<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j5jnvy3je.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="j5jnvy3je"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bird-filled" /></template>
