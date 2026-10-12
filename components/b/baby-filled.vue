<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emgijrbzo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="emgijrbzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:baby-filled" /></template>
