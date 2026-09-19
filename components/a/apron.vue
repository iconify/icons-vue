<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sl-vqabcg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sl-vqabcg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:apron" /></template>
