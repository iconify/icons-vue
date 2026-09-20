<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/amfc7iafx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="amfc7iafx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:battery-low" /></template>
