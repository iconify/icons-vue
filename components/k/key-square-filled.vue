<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u_7gcsazh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u_7gcsazh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:key-square-filled" /></template>
