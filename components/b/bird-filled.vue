<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dfns2cw0z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dfns2cw0z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:bird-filled" /></template>
