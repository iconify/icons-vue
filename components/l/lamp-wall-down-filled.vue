<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fgehs5t-t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fgehs5t-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:lamp-wall-down-filled" /></template>
