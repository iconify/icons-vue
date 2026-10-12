<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c9c6w6k3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c9c6w6k3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:circle-pile-filled" /></template>
