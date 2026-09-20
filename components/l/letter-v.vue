<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n8f04vbvf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n8f04vbvf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:letter-v" /></template>
