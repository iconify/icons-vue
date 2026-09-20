<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d8nck0vqo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d8nck0vqo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:dash" /></template>
