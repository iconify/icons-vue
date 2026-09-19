<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kdif1-9fq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kdif1-9fq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:arrow-right-filled" /></template>
