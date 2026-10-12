<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c6u7_lbof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c6u7_lbof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:dice-3-filled" /></template>
