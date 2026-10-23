<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u3um9q0qi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="u3um9q0qi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:lens-filled" /></template>
