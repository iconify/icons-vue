<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bal2iqxhb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bal2iqxhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:church-fill-round" /></template>
