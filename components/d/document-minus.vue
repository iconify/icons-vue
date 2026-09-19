<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u9v3bbchg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u9v3bbchg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:document-minus" /></template>
