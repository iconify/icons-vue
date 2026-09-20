<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ci8n_z1zm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ci8n_z1zm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:hyper" /></template>
