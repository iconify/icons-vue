<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cz8hf6bxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="cz8hf6bxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:folder-check-outline" /></template>
